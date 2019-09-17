actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: None
joint-interpolation: True
dsr-gait-period: 0.6
critic-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
actor-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
loss-output-diff-coeff: 0
HLC-frequency: 25
filter-torque: False
bullet-default-PD: False
train-step-num: 1
loss-entropy-coeff: 0.0
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
max-test-time: 10
actor-layer-size: [256, 256]
imitation-weight: 0.5
critic-layer-size: [256, 256]
gating-index: None
state-dim: 23
max-step-num: 2500000000
epoch-num: 500
tau: 0.001
dsr-gait-freq: 1.667
actor-weight-decay: 1e-06
task-weight: 0.5
record-start-size: 10000.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-path-num: 20
expert-num: 4
loss-output-bound-coeff: 0.0
action-dim: 12
max-path-step: 5000
LLC-frequency: 500
render-eval: False
interpolation: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
reward-scale: 0.1
prioritized-exp-replay: True
filter-action: True
batch-size: 128
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
rollout-step-num: 1
test-num: 4
total-step-num: 2500000000
replay-start-size: 10000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
n-step: 1
critic-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
critic-lr: 0.0003
gamma: 0.955
gating-layer-size: [32, 32]
gating-activation-fn: ['relu', 'relu', 'None']
squash-action: True
max-train-time: 10
loss-output-smooth-coeff: 2.0
replay-buffer-size: 1000000
critic-weight-decay: 1e-06
actor-lr: 0.0003
actor-l2-reg: 0.0003
Physics-frequency: 1000
max-episode-num: 5000000
