max-episode-num: 5000000
loss-output-bound-coeff: 0.0
critic-lr: 0.0003
train-step-num: 1
loss-entropy-coeff: 0.0
interpolation: False
max-path-step: 5000
prioritized-exp-replay: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
Physics-frequency: 1000
task-weight: 0.5
state-dim: 23
filter-action: True
loss-output-smooth-coeff: 2.0
critic-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.955
replay-ratio: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-diff-coeff: 0
rollout-step-num: 1
HLC-frequency: 25
expert-index: None
joint-interpolation: True
actor-lr: 0.0003
imitation-weight: 0.5
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
n-step: 1
max-path-num: 20
gating-index: None
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
reward-scale: 0.1
render-eval: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-weight-decay: 1e-06
record-start-size: 10000.0
env-id: HumanoidBalanceFilter-v0
critic-activation-fn: ['relu', 'relu', 'None']
expert-num: 4
tau: 0.001
batch-size: 128
actor-layer-size: [256, 256]
epoch-step-num: 5000000
squash-action: True
replay-buffer-size: 1000000
bullet-default-PD: False
total-step-num: 2500000000
replay-start-size: 10000
max-test-time: 10
max-step-num: 2500000000
filter-torque: False
actor-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
LLC-frequency: 500
gating-layer-size: [32, 32]
critic-layer-size: [256, 256]
dsr-gait-freq: 1.667
test-num: 4
dsr-gait-period: 0.6
