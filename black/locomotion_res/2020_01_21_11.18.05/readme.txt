actor-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
tau: 0.001
interpolation: False
task-weight: 0.5
render-eval: False
actor-weight-decay: 1e-06
gating-layer-size: [32, 32]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
epoch-num: 500
loss-output-bound-coeff: 0.0
train-step-num: 1
total-step-num: 2500000000
prioritized-exp-replay: True
critic-weight-decay: 1e-06
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
critic-l2-reg: 0.0003
n-step: 1
max-test-time: 10
critic-layer-size: [256, 256]
actor-lr: 0.0003
actor-l2-reg: 0.0003
gamma: 0.955
bullet-default-PD: False
replay-ratio: 1
replay-buffer-size: 1000000
max-episode-num: 5000000
max-train-time: 10
max-step-num: 2500000000
state-dim: 23
rollout-step-num: 1
dsr-gait-period: 0.6
loss-output-smooth-coeff: 2.0
critic-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
test-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-freq: 1.667
imitation-weight: 0.5
joint-interpolation: True
filter-torque: False
expert-index: None
Physics-frequency: 1000
filter-action: True
loss-output-diff-coeff: 0
actor-layer-size: [256, 256]
LLC-frequency: 500
batch-size: 128
critic-lr: 0.0003
loss-entropy-coeff: 0.0
epoch-step-num: 5000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-start-size: 10000
gating-index: None
action-dim: 12
record-start-size: 10000.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
reward-scale: 0.1
expert-num: 4
squash-action: True
